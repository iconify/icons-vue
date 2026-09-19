<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcbic_sri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pcbic_sri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:flickr4" /></template>

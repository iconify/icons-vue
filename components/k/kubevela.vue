<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n772iyb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":122.5,"height":122.5};
const content = `<path class="n772iyb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kubevela" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttrkhideo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ttrkhideo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:luggage" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3u0qroui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="f3u0qroui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hill-avalanche" /></template>

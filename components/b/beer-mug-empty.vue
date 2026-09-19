<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m68prj4ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m68prj4ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:beer-mug-empty" /></template>

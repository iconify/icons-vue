<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_7gkfb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r_7gkfb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:list-ol-solid" /></template>

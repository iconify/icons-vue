<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzw3sc8yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":37,"height":32};
const content = `<path class="dzw3sc8yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:heart" /></template>

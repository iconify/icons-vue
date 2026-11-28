<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esuzo23md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esuzo23md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:image-star" /></template>

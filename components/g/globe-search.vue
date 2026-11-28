<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwb5omtzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwb5omtzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:globe-search" /></template>

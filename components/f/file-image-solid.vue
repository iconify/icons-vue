<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klauqebsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klauqebsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-image-solid" /></template>

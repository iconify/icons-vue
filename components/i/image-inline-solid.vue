<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-04ptp5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-04ptp5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:image-inline-solid" /></template>

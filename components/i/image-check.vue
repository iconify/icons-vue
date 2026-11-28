<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zphfr0bjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zphfr0bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:image-check" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtrbv7bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtrbv7bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-heart" /></template>

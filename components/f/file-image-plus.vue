<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eej_e7vke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eej_e7vke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-image-plus" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9m6x3g9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9m6x3g9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-image-x" /></template>

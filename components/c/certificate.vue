<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unf09nsdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unf09nsdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:certificate" /></template>

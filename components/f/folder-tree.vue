<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u00ue5b6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="u00ue5b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:folder-tree" /></template>

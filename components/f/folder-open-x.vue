<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do7ui-bvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do7ui-bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folder-open-x" /></template>

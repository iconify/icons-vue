<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9bz4hbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9bz4hbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-zip-plus" /></template>

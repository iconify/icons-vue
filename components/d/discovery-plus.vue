<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luh1e9pxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="luh1e9pxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:discovery-plus" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u53nmsb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u53nmsb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:add-to-library-line" /></template>

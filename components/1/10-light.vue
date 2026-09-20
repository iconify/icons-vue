<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axnrszm_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axnrszm_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:10-light" /></template>

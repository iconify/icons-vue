<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9_rb4bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9_rb4bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folder-lock" /></template>

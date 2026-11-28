<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk_n3_4jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk_n3_4jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folders" /></template>

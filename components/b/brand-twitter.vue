<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_9ma5gfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_9ma5gfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:brand-twitter" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjihztyop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjihztyop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gbex" /></template>

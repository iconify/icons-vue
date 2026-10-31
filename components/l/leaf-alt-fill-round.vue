<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkt1qo2tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkt1qo2tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:leaf-alt-fill-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf2gz2hlr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf2gz2hlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:apps-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuv5mcb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iuv5mcb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:copy-fill" /></template>

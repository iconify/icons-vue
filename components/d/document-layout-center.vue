<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrgwkvp0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrgwkvp0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:document-layout-center" /></template>

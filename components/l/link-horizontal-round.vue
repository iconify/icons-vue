<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2lv_5byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2lv_5byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:link-horizontal-round" /></template>

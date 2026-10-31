<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcwnfy39o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcwnfy39o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:link-break-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/litsavbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="litsavbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-right-to-line-fill-round" /></template>

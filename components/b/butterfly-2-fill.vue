<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue5444bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue5444bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:butterfly-2-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbbtl_qtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbbtl_qtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-starkvind" /></template>

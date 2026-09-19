<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lclse37hi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lclse37hi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:close-circle-2-bold" /></template>

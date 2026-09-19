<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tabi2-kal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tabi2-kal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:link-thin" /></template>

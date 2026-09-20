<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyg202smx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyg202smx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:google" /></template>

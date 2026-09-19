<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irm7knmrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irm7knmrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:input-field" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp30w0h8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp30w0h8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-help-fill-round" /></template>

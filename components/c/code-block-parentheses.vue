<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm52svw0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mm52svw0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:code-block-parentheses" /></template>

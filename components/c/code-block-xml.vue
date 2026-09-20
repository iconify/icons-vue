<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/istlbrwok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="istlbrwok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:code-block-xml" /></template>

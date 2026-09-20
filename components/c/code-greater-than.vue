<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnsfc7b1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnsfc7b1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:code-greater-than" /></template>

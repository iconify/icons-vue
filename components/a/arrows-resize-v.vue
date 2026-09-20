<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehj45xb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehj45xb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrows-resize-v" /></template>

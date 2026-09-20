<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoiqv73_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoiqv73_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:broom-sparkles" /></template>

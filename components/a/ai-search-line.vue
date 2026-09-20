<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx89wjbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx89wjbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-search-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqpo30-3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqpo30-3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-sort-alt-1-fill" /></template>

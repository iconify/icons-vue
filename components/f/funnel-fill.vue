<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj62jbb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jj62jbb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:funnel-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxjuepbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxjuepbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:angle-double-left" /></template>

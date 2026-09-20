<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1ct7n8ui.css';
import '../../css/d/dj56zmboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1ct7n8ui"/><path clip-rule="evenodd" class="dj56zmboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dxgm" /></template>

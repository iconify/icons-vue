<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk_k361gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xk_k361gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:compass-sharp-fill" /></template>

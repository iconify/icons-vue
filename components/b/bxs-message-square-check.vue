<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvhiohvzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvhiohvzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-square-check" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chk-b_b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chk-b_b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bow-tie-fill" /></template>

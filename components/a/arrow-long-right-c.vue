<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkhxtabzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fkhxtabzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrow-long-right-c" /></template>

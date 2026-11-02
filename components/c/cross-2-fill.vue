<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enzq9n-th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enzq9n-th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cross-2-fill" /></template>

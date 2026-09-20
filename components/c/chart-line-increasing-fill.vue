<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq99pwd1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq99pwd1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-line-increasing-fill" /></template>

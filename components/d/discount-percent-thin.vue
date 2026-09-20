<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq5kcq0eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cq5kcq0eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:discount-percent-thin" /></template>

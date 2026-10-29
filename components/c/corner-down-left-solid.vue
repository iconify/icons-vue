<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6hi8ebry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6hi8ebry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:corner-down-left-solid" /></template>

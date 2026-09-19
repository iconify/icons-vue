<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynpjq9bxw.css';
import '../../css/q/q6_bp8una.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynpjq9bxw"/><path class="q6_bp8una"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chess-filled" /></template>

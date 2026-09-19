<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex1imqh0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex1imqh0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:circle-dot-dashed" /></template>

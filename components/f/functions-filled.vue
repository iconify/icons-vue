<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efru-76vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efru-76vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:functions-filled" /></template>

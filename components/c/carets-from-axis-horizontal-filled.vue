<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls1c0037m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls1c0037m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:carets-from-axis-horizontal-filled" /></template>

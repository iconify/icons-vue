<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4zbgebyk.css';
import '../../css/b/bb6-y3inu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4zbgebyk"/><path class="bb6-y3inu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-file-md" /></template>

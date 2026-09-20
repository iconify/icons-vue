<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjkiu1vyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjkiu1vyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:leox" /></template>

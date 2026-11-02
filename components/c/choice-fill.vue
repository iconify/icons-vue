<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1bi4bcir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1bi4bcir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:choice-fill" /></template>

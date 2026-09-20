<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oesj0egjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oesj0egjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:github-fill" /></template>

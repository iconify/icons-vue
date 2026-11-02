<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lit144j4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lit144j4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-end-vertical-line" /></template>

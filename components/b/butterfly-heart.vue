<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh5re7bed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh5re7bed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:butterfly-heart" /></template>

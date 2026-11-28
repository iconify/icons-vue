<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejdqt1mgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejdqt1mgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chess-queen-solid" /></template>

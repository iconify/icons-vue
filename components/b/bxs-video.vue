<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkhlsmt2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkhlsmt2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-video" /></template>

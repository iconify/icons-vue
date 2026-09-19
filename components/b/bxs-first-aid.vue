<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v688eqkfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v688eqkfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-first-aid" /></template>

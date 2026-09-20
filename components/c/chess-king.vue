<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otjif-b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otjif-b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chess-king" /></template>

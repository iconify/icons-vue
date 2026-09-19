<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1u15frkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1u15frkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:comment-03" /></template>

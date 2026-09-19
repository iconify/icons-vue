<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh3q47n9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh3q47n9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:chat" /></template>

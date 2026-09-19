<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp-an5bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kp-an5bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:h3" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw0dqye1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw0dqye1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-lock-fill" /></template>

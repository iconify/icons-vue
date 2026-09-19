<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjhzikvqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjhzikvqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:curly-brackets" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_zh3nbon.css';
import '../../css/f/f-euyubsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_zh3nbon"/><path class="f-euyubsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:inbox-question-mark-fill" /></template>

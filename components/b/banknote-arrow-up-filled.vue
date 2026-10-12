<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtrl803vx.css';
import '../../css/e/e0-stmb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtrl803vx"/><path clip-rule="evenodd" class="e0-stmb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:banknote-arrow-up-filled" /></template>

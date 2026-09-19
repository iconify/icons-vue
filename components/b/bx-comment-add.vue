<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch6_fcbjy.css';
import '../../css/j/j1kdqfrps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch6_fcbjy"/><path class="j1kdqfrps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-comment-add" /></template>

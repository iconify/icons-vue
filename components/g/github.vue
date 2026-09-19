<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr1nhacmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="kr1nhacmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:github" /></template>

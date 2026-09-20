<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql8l1nbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql8l1nbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:defx" /></template>

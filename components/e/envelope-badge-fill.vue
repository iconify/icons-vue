<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inixre9_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="inixre9_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:envelope-badge-fill" /></template>

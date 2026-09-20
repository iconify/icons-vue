<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpx0ywb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpx0ywb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-check" /></template>

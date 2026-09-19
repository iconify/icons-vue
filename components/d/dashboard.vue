<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj7v0vbun.css';
import '../../css/i/i28xa4bkq.css';
import '../../css/f/fli27abct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer fj7v0vbun"/><path class="duoicon-primary-layer i28xa4bkq"/><path class="duoicon-secondary-layer fli27abct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:dashboard" /></template>

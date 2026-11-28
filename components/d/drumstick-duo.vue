<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v99-kxb3s.css';
import '../../css/j/j0jt8n8se.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary v99-kxb3s"/><path class="j0jt8n8se primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:drumstick-duo" /></template>

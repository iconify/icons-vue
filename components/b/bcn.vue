<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm8snjsbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm8snjsbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bcn" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6_k4tf6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d6_k4tf6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bigsb" /></template>

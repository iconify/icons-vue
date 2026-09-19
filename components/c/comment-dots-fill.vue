<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dizz0gbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dizz0gbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:comment-dots-fill" /></template>

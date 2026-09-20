<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drritlt1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="drritlt1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:home-fill" /></template>

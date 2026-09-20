<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj7t9lb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj7t9lb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gravity" /></template>

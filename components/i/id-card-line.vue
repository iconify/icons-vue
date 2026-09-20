<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk-2vtw8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk-2vtw8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:id-card-line" /></template>

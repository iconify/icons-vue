<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_31tmbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_31tmbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-circle-plus" /></template>

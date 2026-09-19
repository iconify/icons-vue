<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_3_c0b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_3_c0b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-circle-text" /></template>

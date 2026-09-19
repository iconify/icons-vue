<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4ghhtb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4ghhtb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-circle-alert" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzqznfbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzqznfbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chat-add" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyr3-ccue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyr3-ccue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-smile-line" /></template>

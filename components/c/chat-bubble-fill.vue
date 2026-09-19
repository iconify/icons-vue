<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk-agabqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gk-agabqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chat-bubble-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi3-nmwyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi3-nmwyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-bubble-cancel-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01uxbc_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h01uxbc_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:chat-bubble-oval-flat" /></template>

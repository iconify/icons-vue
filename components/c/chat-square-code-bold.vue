<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxj5tzieu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cxj5tzieu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-code-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdhe5xgri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mdhe5xgri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-bubble-cancel" /></template>

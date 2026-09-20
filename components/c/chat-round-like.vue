<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v26cdt2bo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v26cdt2bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-round-like" /></template>

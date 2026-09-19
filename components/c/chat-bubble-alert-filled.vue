<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7vu07rmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7vu07rmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-bubble-alert-filled" /></template>

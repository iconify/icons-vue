<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve6b9o9st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve6b9o9st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:chat-bubble-error" /></template>

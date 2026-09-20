<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbqy7xyjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbqy7xyjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chat-bubble-outline" /></template>

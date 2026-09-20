<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewd3j3yhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewd3j3yhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chat-alert-outline" /></template>

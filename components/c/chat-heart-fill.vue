<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di5-yddwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di5-yddwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-heart-fill" /></template>

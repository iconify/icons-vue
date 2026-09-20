<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em3wahoxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em3wahoxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-private-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpe488jpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lpe488jpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-dots-bold" /></template>

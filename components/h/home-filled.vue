<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhjf3bc8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fhjf3bc8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:home-filled" /></template>

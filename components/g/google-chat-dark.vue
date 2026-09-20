<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xul7zyimb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xul7zyimb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-chat-dark" /></template>

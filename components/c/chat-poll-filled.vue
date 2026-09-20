<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j224f_kyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j224f_kyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chat-poll-filled" /></template>

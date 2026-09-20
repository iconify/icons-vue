<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlvrikcub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlvrikcub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:chat-2" /></template>

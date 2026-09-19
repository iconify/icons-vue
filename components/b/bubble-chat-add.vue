<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n19k09bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n19k09bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bubble-chat-add" /></template>

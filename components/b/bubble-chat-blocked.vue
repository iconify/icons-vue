<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezlqj9b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezlqj9b5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bubble-chat-blocked" /></template>

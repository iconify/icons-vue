<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guyoekzui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guyoekzui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-minus-round" /></template>

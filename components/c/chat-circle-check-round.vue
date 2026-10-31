<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oivi-4bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oivi-4bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-check-round" /></template>

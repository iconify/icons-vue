<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofpgi6bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ofpgi6bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:chat-bubble-left" /></template>

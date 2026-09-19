<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-5_y5zdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m-5_y5zdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-left-20-solid" /></template>

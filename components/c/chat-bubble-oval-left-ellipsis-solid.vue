<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg73f3bvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tg73f3bvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-oval-left-ellipsis-solid" /></template>

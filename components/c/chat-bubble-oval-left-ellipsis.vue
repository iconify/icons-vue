<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czxf_zkwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czxf_zkwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-oval-left-ellipsis" /></template>

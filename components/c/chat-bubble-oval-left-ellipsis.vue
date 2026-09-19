<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1p_cwb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1p_cwb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:chat-bubble-oval-left-ellipsis" /></template>

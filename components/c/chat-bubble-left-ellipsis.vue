<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqe1pt4jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqe1pt4jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-left-ellipsis" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwqapu5pq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwqapu5pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:chat-alt-2-light" /></template>

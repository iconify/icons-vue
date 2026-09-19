<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdmzamy-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":520,"height":512};
const content = `<path class="qdmzamy-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:chat-alt" /></template>

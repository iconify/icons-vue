<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pagw__b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pagw__b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:chat-bubble-left-right" /></template>

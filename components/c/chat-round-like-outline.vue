<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ninr9tbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ninr9tbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-like-outline" /></template>

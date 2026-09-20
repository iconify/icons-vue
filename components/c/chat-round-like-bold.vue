<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwx4n85mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zwx4n85mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-like-bold" /></template>

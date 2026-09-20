<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beg3fv-xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="beg3fv-xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-check-outline" /></template>

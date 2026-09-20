<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f8yqsxb0s.css';
import '../../css/l/lv7agqbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle transform="matrix(-1 0 0 1 22 2)" class="f8yqsxb0s"/><path class="lv7agqbid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-unread-broken" /></template>

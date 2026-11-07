<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_-5r-bwo.css';
import '../../css/x/x9024bb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_-5r-bwo"/><path clip-rule="evenodd" class="x9024bb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-replay-outline" /></template>

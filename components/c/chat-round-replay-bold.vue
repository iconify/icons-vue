<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd1hczb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rd1hczb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-replay-bold" /></template>

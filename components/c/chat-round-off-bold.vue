<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghj3bdbyn.css';
import '../../css/s/sibe-iawq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghj3bdbyn"/><path class="sibe-iawq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-off-bold" /></template>

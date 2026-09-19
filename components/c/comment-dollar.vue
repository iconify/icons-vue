<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bot_9nbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bot_9nbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:comment-dollar" /></template>

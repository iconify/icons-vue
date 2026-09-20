<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp2pneo0a.css';
import '../../css/p/p76fyjzyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp2pneo0a"/><path class="p76fyjzyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:doge-filled" /></template>

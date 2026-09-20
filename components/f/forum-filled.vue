<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv654bc7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv654bc7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:forum-filled" /></template>

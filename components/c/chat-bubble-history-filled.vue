<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pak4c7bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pak4c7bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chat-bubble-history-filled" /></template>

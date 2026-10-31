<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6ax11bjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6ax11bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-settings-corner-fill-round" /></template>

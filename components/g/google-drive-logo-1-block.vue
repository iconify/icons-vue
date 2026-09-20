<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2pjjkbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n2pjjkbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-drive-logo-1-block" /></template>

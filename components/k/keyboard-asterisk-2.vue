<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pned3bcjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pned3bcjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:keyboard-asterisk-2" /></template>

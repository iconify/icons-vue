<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn0n5kbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn0n5kbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:disconnected-circle-filled" /></template>

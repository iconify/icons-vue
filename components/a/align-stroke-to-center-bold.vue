<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xktn4bb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xktn4bb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:align-stroke-to-center-bold" /></template>

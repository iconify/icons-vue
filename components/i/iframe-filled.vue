<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs9d7db8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs9d7db8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:iframe-filled" /></template>

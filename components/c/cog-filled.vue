<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex7uwkbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex7uwkbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cog-filled" /></template>

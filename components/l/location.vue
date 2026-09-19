<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry3so7gim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry3so7gim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:location" /></template>

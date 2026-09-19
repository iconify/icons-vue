<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp43f2bdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp43f2bdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:donate-heart" /></template>

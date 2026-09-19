<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo9kftbtp.css';
import '../../css/u/u5zp6vbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo9kftbtp"/><path class="u5zp6vbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:broadcast-filled" /></template>

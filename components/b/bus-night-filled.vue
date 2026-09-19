<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd5blcbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xd5blcbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bus-night-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsc84ccge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsc84ccge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-t-square" /></template>

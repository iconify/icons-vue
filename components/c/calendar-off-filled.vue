<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhy62g6ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yhy62g6ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:calendar-off-filled" /></template>

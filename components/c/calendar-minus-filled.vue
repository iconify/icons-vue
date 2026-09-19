<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd7jidc8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xd7jidc8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:calendar-minus-filled" /></template>

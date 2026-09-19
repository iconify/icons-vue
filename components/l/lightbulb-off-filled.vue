<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5nha0b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w5nha0b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:lightbulb-off-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wozf3nhyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wozf3nhyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:celebrate-fill" /></template>

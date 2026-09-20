<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb5oamwpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zb5oamwpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bag3-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_5qqfbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j_5qqfbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-to-down-right-filled" /></template>

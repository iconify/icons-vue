<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt-fu6bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt-fu6bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:collapse-horizontal-fill" /></template>

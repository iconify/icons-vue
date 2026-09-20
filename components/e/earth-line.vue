<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt_a2obgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt_a2obgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:earth-line" /></template>

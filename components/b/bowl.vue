<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi02debtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vi02debtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:bowl" /></template>

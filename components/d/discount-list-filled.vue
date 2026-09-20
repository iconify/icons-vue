<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy6voyb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy6voyb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:discount-list-filled" /></template>

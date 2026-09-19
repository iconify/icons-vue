<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f681u-1lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f681u-1lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clock-4-filled" /></template>

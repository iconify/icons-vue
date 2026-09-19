<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3j4zebqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3j4zebqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:corner-up-left-outline" /></template>

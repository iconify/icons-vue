<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxc5c4b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxc5c4b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:color-picker" /></template>

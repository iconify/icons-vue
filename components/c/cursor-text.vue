<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdo-7rb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdo-7rb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cursor-text" /></template>

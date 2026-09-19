<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhq3foupt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhq3foupt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-flag-alt" /></template>

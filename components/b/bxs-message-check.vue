<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l19c6bchs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l19c6bchs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-check" /></template>

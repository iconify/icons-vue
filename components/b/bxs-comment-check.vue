<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxt-x2bhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxt-x2bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-comment-check" /></template>

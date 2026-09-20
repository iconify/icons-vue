<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8u1chjgn.css';
import '../../css/x/xl35czbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8u1chjgn"/><path class="xl35czbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:comment-2-fill" /></template>

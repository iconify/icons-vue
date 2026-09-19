<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhnvhibms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhnvhibms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:comment-dots" /></template>

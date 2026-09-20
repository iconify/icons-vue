<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw1iew.css';
import '../../css/o/odwtxx.css';
import '../../css/e/efzwqq.css';
import '../../css/s/so-from-8.css';
import '../../css/s/so-to-0.css';
import '../../css/f/fill-to-1.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew odwtxx"/><path class="efzwqq iw1iew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:computer-filled" /></template>

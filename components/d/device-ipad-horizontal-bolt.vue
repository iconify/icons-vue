<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko8ti6cjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko8ti6cjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-horizontal-bolt" /></template>

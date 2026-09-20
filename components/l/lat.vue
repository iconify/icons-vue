<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko6i3z5qf.css';
import '../../css/o/oowixtbky.css';
import '../../css/t/tggvt9bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko6i3z5qf"/><path class="oowixtbky"/><path class="tggvt9bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lat" /></template>

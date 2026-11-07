<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goaxqgbme.css';
import '../../css/q/qpih9sbik.css';
import '../../css/w/wm3j448rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="goaxqgbme"/><path class="qpih9sbik"/><path class="wm3j448rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-image-bold" /></template>

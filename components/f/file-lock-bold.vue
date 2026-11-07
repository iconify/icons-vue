<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq-7flbbr.css';
import '../../css/b/b0bcc0c-v.css';
import '../../css/z/z5kr1gbqy.css';
import '../../css/w/wm3j448rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq-7flbbr"/><path class="b0bcc0c-v"/><path clip-rule="evenodd" class="z5kr1gbqy"/><path class="wm3j448rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-lock-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbsst6bep.css';
import '../../css/h/h7gro1emj.css';
import '../../css/r/r3sjlmblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xbsst6bep"/><path class="h7gro1emj"/><path class="r3sjlmblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:coin" /></template>

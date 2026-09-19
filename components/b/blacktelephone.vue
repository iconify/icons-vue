<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inrii0mwj.css';
import '../../css/y/yukot35yn.css';
import '../../css/c/ctunfubbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="inrii0mwj"/><path class="yukot35yn"/><path class="ctunfubbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:blacktelephone" /></template>

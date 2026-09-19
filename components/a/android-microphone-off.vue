<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktwpc4lka.css';
import '../../css/z/zfvalbp8b.css';
import '../../css/w/wh0krirqr.css';
import '../../css/s/sosnt7a2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ktwpc4lka"/><path class="zfvalbp8b"/><path class="wh0krirqr"/><path class="sosnt7a2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-microphone-off" /></template>

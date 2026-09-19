<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqj83jaxk.css';
import '../../css/p/pi1-wer9v.css';
import '../../css/o/oom0uccvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kqj83jaxk"/><path class="pi1-wer9v"/><path class="oom0uccvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:cjkunifiedideograph-c" /></template>

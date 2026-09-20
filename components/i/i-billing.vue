<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkps9h2bk.css';
import '../../css/q/q40219bwz.css';
import '../../css/r/rqyk8bb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hkps9h2bk"/><path class="q40219bwz"/><path class="rqyk8bb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-billing" /></template>

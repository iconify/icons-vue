<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qokjj-kmj.css';
import '../../css/a/a8vsq7owx.css';
import '../../css/p/pu0j68bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qokjj-kmj"/><path class="a8vsq7owx"/><path class="pu0j68bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:blade-pitch-20-bold" /></template>

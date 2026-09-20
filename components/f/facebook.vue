<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4y-sm.css';
import '../../css/o/oxmpwq.css';
import '../../css/j/jd_9zf.css';
import '../../css/s/so-from-24.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4y-sm oxmpwq"/><path class="jd_9zf oxmpwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:facebook" /></template>

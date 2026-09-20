<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd07yqmly.css';
import '../../css/z/zlrwl1bnk.css';
import '../../css/l/lstaoj3fp.css';
import '../../css/i/i7sr6ubzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd07yqmly"/><path class="zlrwl1bnk"/><path class="lstaoj3fp"/><path class="i7sr6ubzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:hockey-mask" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_uz53-xm.css';
import '../../css/g/g_a2zwbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l_uz53-xm"/><path class="g_a2zwbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:crop" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg7hmzy4m.css';
import '../../css/j/jh2kfpbhx.css';
import '../../css/k/k79q3xboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gg7hmzy4m"/><path class="jh2kfpbhx"/><circle class="k79q3xboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:image-lock-ltr" /></template>

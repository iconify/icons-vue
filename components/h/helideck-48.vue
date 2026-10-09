<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-j1i2muo.css';
import '../../css/q/qxu7-jb9g.css';
import '../../css/e/e647zfbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c-j1i2muo"/><path class="qxu7-jb9g"/><path class="e647zfbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:helideck-48" /></template>

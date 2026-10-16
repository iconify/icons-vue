<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt6bg53-l.css';
import '../../css/x/xc-gyrbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wt6bg53-l"/><path class="xc-gyrbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:extension-lead-48-bold" /></template>

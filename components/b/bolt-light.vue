<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdj-7nb0w.css';
import '../../css/t/tbhf0lycc.css';
import '../../css/w/wei4ynt1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":160,"height":68.7,"top":45.65};
const content = `<path class="gdj-7nb0w"/><path class="tbhf0lycc"/><path class="wei4ynt1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bolt-light" /></template>

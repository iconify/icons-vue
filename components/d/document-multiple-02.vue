<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0g6n4nwz.css';
import '../../css/z/zn9kz8x1i.css';
import '../../css/f/f2zhg8brw.css';
import '../../css/l/lza6dyowd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y0g6n4nwz"/><path class="zn9kz8x1i"/><path class="f2zhg8brw"/><path class="lza6dyowd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-multiple-02" /></template>

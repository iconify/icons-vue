<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs5l9tbhg.css';
import '../../css/y/ys0s8unky.css';
import '../../css/a/as9i7h0ds.css';
import '../../css/f/fqeyirbjk.css';
import '../../css/z/z6463wkhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-shadow zs5l9tbhg"/><path class="wm-k ys0s8unky"/><path class="as9i7h0ds wm-k"/><path class="fqeyirbjk wm-s"/><path class="wm-s z6463wkhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:list-minus" /></template>

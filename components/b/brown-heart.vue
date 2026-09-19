<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xbygc4bqp.css';
import '../../css/o/obs24acsp.css';
import '../../css/o/o_uhbsp1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="xbygc4bqp"/><path class="obs24acsp"/><ellipse transform="rotate(30 23.477 12.594)" class="o_uhbsp1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:brown-heart" /></template>

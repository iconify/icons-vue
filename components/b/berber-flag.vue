<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcpth-wqs.css';
import '../../css/c/c87urq4yy.css';
import '../../css/r/ryuchjvkn.css';
import '../../css/z/z8ntjqb8q.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="wcpth-wqs"/><path class="c87urq4yy"/><path class="ryuchjvkn"/><path class="z8ntjqb8q"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:berber-flag" /></template>

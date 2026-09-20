<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkq7-hbwz.css';
import '../../css/j/jrsmtbc7d.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="jkq7-hbwz"/><rect transform="rotate(30 40 38)" class="jrsmtbc7d"/><rect transform="rotate(-30 31 36)" class="jrsmtbc7d"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:alabama-flag" /></template>

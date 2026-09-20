<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydht5db_k.css';
import '../../css/d/dusa4681d.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ydht5db_k"/><path class="dusa4681d"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:bari-flag" /></template>

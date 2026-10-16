<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7m7xy44u.css';
import '../../css/t/t5jb97bqd.css';
import '../../css/c/cxsgvgbjp.css';
import '../../css/k/k413g3b0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j7m7xy44u"/><path class="t5jb97bqd"/><path class="cxsgvgbjp"/><path class="k413g3b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lightning-protection-20-bold" /></template>

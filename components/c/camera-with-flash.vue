<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq4blkbef.css';
import '../../css/w/w1qn6ebub.css';
import '../../css/j/jzb9_sbtv.css';
import '../../css/g/g0pho4opl.css';
import '../../css/g/g97vel3fj.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/s/sj7no8b9h.css';
import '../../css/z/zh3g2pkap.css';
import '../../css/b/b_84chben.css';
import '../../css/p/pjurphodb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="zq4blkbef"/><path class="w1qn6ebub"/><path class="jzb9_sbtv"/><path class="g0pho4opl"/><path class="g97vel3fj"/><g class="jn8qy4bru"><path class="sj7no8b9h"/><path class="zh3g2pkap"/><circle class="b_84chben"/><path class="pjurphodb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:camera-with-flash" /></template>

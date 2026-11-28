<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2ku2kb3t.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f3326pq5l.css';
import '../../css/l/lnuqcu1vn.css';
import '../../css/o/o6rrpwbqi.css';
import '../../css/q/qhiifsb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary y2ku2kb3t"/><g class="dt0cm9dhy primary"><path class="f3326pq5l"/><path class="lnuqcu1vn"/><path class="o6rrpwbqi"/><path class="qhiifsb6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layout-bento-duo" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/hn_ya--lb.css';
import '../../css/i/i2gopvbal.css';
import '../../css/w/wcq4uobzg.css';
import '../../css/f/fm6mptjkl.css';
import '../../css/u/u3tvnyuho.css';
import '../../css/h/h8meh3bxh.css';
import '../../css/u/u5u1m-14r.css';
import '../../css/k/kur4pt1jx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hn_ya--lb"/><path class="i2gopvbal"/><path class="wcq4uobzg"/><path class="fm6mptjkl"/><path class="u3tvnyuho"/><path class="h8meh3bxh"/><path class="u5u1m-14r"/><path class="kur4pt1jx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:loader" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcpth-wqs.css';
import '../../css/p/pi7jdd7uf.css';
import '../../css/k/k4zcbrbym.css';
import '../../css/z/zj93wib6z.css';
import '../../css/f/f2eiwubox.css';
import '../../css/f/fywslsbyr.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="wcpth-wqs"/><path class="pi7jdd7uf"/><path class="k4zcbrbym"/><path class="zj93wib6z"/><ellipse class="f2eiwubox"/><path class="fywslsbyr"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-andorra" /></template>

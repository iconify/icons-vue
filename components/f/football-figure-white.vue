<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcf6_w18s.css';
import '../../css/b/btt_r2bcj.css';
import '../../css/w/wr35f_b0v.css';
import '../../css/w/wz-xm5jiv.css';
import '../../css/s/sl7hd2bim.css';
import '../../css/d/d9z-87btf.css';
import '../../css/r/rz0zd9b0a.css';
import '../../css/w/wwf5bcyfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="tcf6_w18s"/><path class="btt_r2bcj"/><path class="wr35f_b0v"/><path class="wz-xm5jiv"/><path class="sl7hd2bim"/><path class="d9z-87btf"/><path class="rz0zd9b0a"/><circle class="wwf5bcyfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:football-figure-white" /></template>

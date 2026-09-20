<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5xdmn.css';
import '../../css/f/fzr6uv.css';
import '../../css/z/zxndow.css';
import '../../css/w/wa90th.css';
import '../../css/c/cm1sdh.css';
import '../../css/o/oxx-om.css';
import '../../css/b/botfzx.css';
import '../../css/g/gd_4-q.css';
import '../../css/s/so-from-50.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVG5Fu2cbEb"><path class="c5xdmn fzr6uv zxndow"/><path class="c5xdmn wa90th zxndow"/><path class="c5xdmn cm1sdh oxx-om"/></mask></defs><path mask="url(#SVG5Fu2cbEb)" class="botfzx"/><path class="c5xdmn cm1sdh gd_4-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:laptop-off" /></template>

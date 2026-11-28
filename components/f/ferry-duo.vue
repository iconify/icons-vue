<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1-b20i-a.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jl645lb9f.css';
import '../../css/f/fv8oh4bhj.css';
import '../../css/g/gqgoc3zwf.css';
import '../../css/v/v40rh9biz.css';
import '../../css/r/r5ne6zgrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1-b20i-a secondary"/><g class="dt0cm9dhy primary"><path class="jl645lb9f"/><path class="fv8oh4bhj"/><path class="gqgoc3zwf"/><path class="v40rh9biz"/><path class="r5ne6zgrx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ferry-duo" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whq2bz03s.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bajt83jld.css';
import '../../css/z/zqedzh64t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary whq2bz03s"/><g class="dt0cm9dhy primary"><path class="bajt83jld"/><path class="zqedzh64t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:egg-duo" /></template>

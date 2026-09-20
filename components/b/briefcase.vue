<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgg9nrbuq.css';
import '../../css/z/zedf9pzpz.css';
import '../../css/p/pj_ax6bww.css';
import '../../css/k/kcm6f8bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgg9nrbuq"/><path class="zedf9pzpz"/><path class="pj_ax6bww"/><path class="kcm6f8bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:briefcase" /></template>

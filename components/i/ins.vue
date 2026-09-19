<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gky7xcbgs.css';
import '../../css/d/d26v317vg.css';
import '../../css/r/rz833ubgc.css';
import '../../css/f/fg974bc0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="gky7xcbgs"/><g class="d26v317vg"><path class="rz833ubgc"/><path class="fg974bc0y"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:ins" /></template>

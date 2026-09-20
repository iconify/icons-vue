<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzlkm6bkg.css';
import '../../css/u/u65lgdc6d.css';
import '../../css/m/msy7dmbdy.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="nzlkm6bkg"/><path class="u65lgdc6d"/><path class="msy7dmbdy"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:genderqueer" /></template>

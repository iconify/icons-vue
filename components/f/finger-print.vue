<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf8q0slyc.css';
import '../../css/u/ukroeg7me.css';
import '../../css/e/emfunmbju.css';
import '../../css/f/f76sgsh0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kf8q0slyc"/><path class="ukroeg7me"/><path class="emfunmbju"/><path class="f76sgsh0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:finger-print" /></template>

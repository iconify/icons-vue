<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fizl9pbgx.css';
import '../../css/n/nq7w58mhy.css';
import '../../css/k/kh_i8p3mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="fizl9pbgx"/><path class="nq7w58mhy"/><path class="kh_i8p3mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:forceps" /></template>

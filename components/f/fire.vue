<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcreuacyk.css';
import '../../css/u/ur8upeb-i.css';
import '../../css/b/bpoy8jcsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="kcreuacyk"/><path class="ur8upeb-i"/><path class="bpoy8jcsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:fire" /></template>

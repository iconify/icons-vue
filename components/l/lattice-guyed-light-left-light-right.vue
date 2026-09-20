<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngjzxub7r.css';
import '../../css/j/j3ukne2vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ngjzxub7r"/><path class="j3ukne2vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:lattice-guyed-light-left-light-right" /></template>

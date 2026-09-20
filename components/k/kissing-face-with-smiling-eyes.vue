<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az7hstbmu.css';
import '../../css/d/dcqdxh5zc.css';
import '../../css/o/o3rhviknj.css';
import '../../css/s/sgor8wbzm.css';
import '../../css/o/oteit1bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="az7hstbmu"/><g class="dcqdxh5zc"><path class="o3rhviknj"/><circle class="sgor8wbzm"/><path class="oteit1bml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:kissing-face-with-smiling-eyes" /></template>

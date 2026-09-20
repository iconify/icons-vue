<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj5kz30al.css';
import '../../css/n/nj0ynib6i.css';
import '../../css/r/r_993qgax.css';
import '../../css/u/ume3owb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bj5kz30al"/><path class="nj0ynib6i"/><path class="r_993qgax"/><path class="ume3owb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:dart" /></template>

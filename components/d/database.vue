<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp6bi8wch.css';
import '../../css/z/zt78mr5_d.css';
import '../../css/u/ud65yub8l.css';
import '../../css/k/ktn4yab2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hp6bi8wch"/><path class="zt78mr5_d"/><path class="ud65yub8l"/><path class="ktn4yab2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:database" /></template>

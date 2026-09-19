<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/e/ehipm2b3p.css';
import '../../css/d/d26v317vg.css';
import '../../css/k/kp7mr8b2k.css';
import '../../css/d/d64x45bya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="ehipm2b3p"/><g class="d26v317vg"><path class="kp7mr8b2k"/><path class="d64x45bya"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:hpb" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxg94rb_l.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/t/t9rd3ac0o.css';
import '../../css/u/ujpkbubht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="bxg94rb_l"/><g class="ij2x_72vy"><path class="t9rd3ac0o"/><path class="ujpkbubht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flamingo" /></template>

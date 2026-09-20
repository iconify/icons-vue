<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6ox5eb0v.css';
import '../../css/b/b00q3hb-i.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/z/zv4wmrb6f.css';
import '../../css/x/xs8nfnbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="q6ox5eb0v"/><path class="b00q3hb-i"/><g class="ij2x_72vy"><path class="zv4wmrb6f"/><path class="xs8nfnbka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:bread" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aix_vvb3p.css';
import '../../css/i/i_7li5bcr.css';
import '../../css/i/ij0_k0b-a.css';
import '../../css/k/ki9cgaciu.css';
import '../../css/o/o0yl_2b-a.css';
import '../../css/m/mj-w1e0oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aix_vvb3p"/><path class="i_7li5bcr"/><path class="ij0_k0b-a"/><path class="ki9cgaciu"/><path class="o0yl_2b-a"/><path class="mj-w1e0oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:download-study" /></template>

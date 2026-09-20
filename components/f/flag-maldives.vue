<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wism3vaym.css';
import '../../css/c/c2j3pfqwl.css';
import '../../css/e/exy3993hn.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="wism3vaym"/><path class="c2j3pfqwl"/><path class="exy3993hn"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-maldives" /></template>

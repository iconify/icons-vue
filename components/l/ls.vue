<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/nw7rk_lec.css';
import '../../css/r/rkats6bfp.css';
import '../../css/c/c-wu24bqc.css';
import '../../css/o/ocyyo8bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":200};
const content = `<g class="bi12bsetm"><path class="nw7rk_lec"/><path class="rkats6bfp"/><path class="c-wu24bqc"/><path class="ocyyo8bxi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cif:ls" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zt0gceb0n.css';
import '../../css/u/ub4d63l7m.css';
import '../../css/a/ay4kxuviq.css';
import '../../css/l/lg3vobc5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(2 2)" class="bi12bsetm"><circle class="zt0gceb0n"/><circle class="ub4d63l7m"/><circle class="ay4kxuviq"/><path class="lg3vobc5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:face-neutral" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r-3a5bbik.css';
import '../../css/b/bsqcx1bor.css';
import '../../css/o/oggwxdwdm.css';
import '../../css/o/os9ahhbmr.css';
import '../../css/a/ahbanjx3m.css';
import '../../css/n/np05gjbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="r-3a5bbik"/><path class="bsqcx1bor"/><path class="oggwxdwdm"/><path class="os9ahhbmr"/><path class="ahbanjx3m"/><path class="np05gjbzu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:hedgehog" /></template>

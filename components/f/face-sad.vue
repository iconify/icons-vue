<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/nb9iv5bjp.css';
import '../../css/u/ub4d63l7m.css';
import '../../css/a/ay4kxuviq.css';
import '../../css/b/bcco9ob2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(2 2)" class="bi12bsetm"><path class="nb9iv5bjp"/><circle class="ub4d63l7m"/><circle class="ay4kxuviq"/><path class="bcco9ob2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:face-sad" /></template>

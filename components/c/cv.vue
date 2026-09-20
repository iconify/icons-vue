<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c6x-byb1z.css';
import '../../css/l/ltc0qfcyk.css';
import '../../css/n/n7jhs1bil.css';
import '../../css/e/ezbn6olzb.css';
import '../../css/b/b9vzy7r5m.css';
import '../../css/v/v07q0rm0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="c6x-byb1z"/><path class="ltc0qfcyk"/><path clip-rule="evenodd" class="n7jhs1bil"/><path class="ezbn6olzb"/><path class="b9vzy7r5m"/><path clip-rule="evenodd" class="v07q0rm0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:cv" /></template>

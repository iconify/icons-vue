<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/psv_8pbss.css';
import '../../css/i/i7tc81bve.css';
import '../../css/w/whc5wl3cy.css';
import '../../css/w/ww0ngzbye.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="psv_8pbss"/><path clip-rule="evenodd" class="i7tc81bve"/><path clip-rule="evenodd" class="whc5wl3cy"/><path class="ww0ngzbye"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:eye-circle" /></template>

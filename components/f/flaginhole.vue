<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asm-7qbsk.css';
import '../../css/h/hl_9gq79s.css';
import '../../css/j/js9boidqq.css';
import '../../css/q/qm671n1cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="asm-7qbsk"/><ellipse class="hl_9gq79s"/><path class="js9boidqq"/><path class="qm671n1cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:flaginhole" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr99i5n7d.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/agcigacbg.css';
import '../../css/g/gm-xp2qic.css';
import '../../css/r/r6y_hob0j.css';
import '../../css/n/nwwepk7cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr99i5n7d secondary"/><g class="dt0cm9dhy primary"><path class="agcigacbg"/><path class="gm-xp2qic"/><path class="r6y_hob0j"/><path class="nwwepk7cy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:locker-duo" /></template>

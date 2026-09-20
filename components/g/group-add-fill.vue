<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n6xinhc7m.css';
import '../../css/s/s1j3mcc6y.css';
import '../../css/y/y04-dybqr.css';
import '../../css/e/ehr251j0l.css';
import '../../css/l/ly3c7gnpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="n6xinhc7m"/><path clip-rule="evenodd" class="s1j3mcc6y"/><path class="y04-dybqr"/><path clip-rule="evenodd" class="ehr251j0l"/><path class="ly3c7gnpg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:group-add-fill" /></template>

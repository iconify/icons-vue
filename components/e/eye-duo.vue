<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab-gq9bkn.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dmesvbbbc.css';
import '../../css/g/gz3bf3izr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab-gq9bkn secondary"/><g class="dt0cm9dhy primary"><path class="dmesvbbbc"/><circle class="gz3bf3izr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:eye-duo" /></template>

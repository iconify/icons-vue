<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jr3bsib-a.css';
import '../../css/e/e-ty3sknj.css';
import '../../css/u/utjknldjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jr3bsib-a"/><path class="e-ty3sknj"/><path class="utjknldjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-up-az" /></template>

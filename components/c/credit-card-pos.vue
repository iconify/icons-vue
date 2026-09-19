<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/ovsdc6bkd.css';
import '../../css/r/rymh20rko.css';
import '../../css/o/o05ivylqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ovsdc6bkd"/><path class="rymh20rko"/><path class="o05ivylqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:credit-card-pos" /></template>

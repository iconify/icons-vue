<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xs--b7q-p.css';
import '../../css/o/omucacchp.css';
import '../../css/p/p82t7hb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xs--b7q-p"/><path class="omucacchp"/><path class="p82t7hb7i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:box-question-mark" /></template>

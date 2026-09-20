<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgyi2j3xy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xgyi2j3xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dropwizard" /></template>

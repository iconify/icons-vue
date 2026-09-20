<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8ajiubdt.css';
import '../../css/q/qw3mm7brb.css';
import '../../css/y/ypjkckbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="g8ajiubdt"/><path class="qw3mm7brb"/><path class="ypjkckbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:cucumber" /></template>

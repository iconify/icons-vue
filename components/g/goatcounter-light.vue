<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3tfe5b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z3tfe5b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:goatcounter-light" /></template>

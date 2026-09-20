<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_eg9t9sm.css';
import '../../css/m/mw3jqjowb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_eg9t9sm"/><path class="mw3jqjowb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grimoire-ttrpg" /></template>

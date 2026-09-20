<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk9v8kbfn.css';
import '../../css/v/v2szjrygp.css';
import '../../css/t/tzko94lia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="uk9v8kbfn"/><path class="v2szjrygp"/><path class="tzko94lia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:dvd" /></template>

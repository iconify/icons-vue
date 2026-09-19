<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi10br14x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mi10br14x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:emptynotepage" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an8dwl38i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="an8dwl38i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:glinr-dark" /></template>

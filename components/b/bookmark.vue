<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocsnh9b9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ocsnh9b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:bookmark" /></template>

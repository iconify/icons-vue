<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk3dn9a9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fk3dn9a9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:arrow-thick-to-bottom" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvr2fkdlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dvr2fkdlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:fourleafclover" /></template>

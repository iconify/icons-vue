<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp0t9zbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vp0t9zbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:hand-point-left" /></template>

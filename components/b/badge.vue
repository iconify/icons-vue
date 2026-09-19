<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q__y2nbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q__y2nbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:badge" /></template>

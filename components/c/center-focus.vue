<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do3z1_b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="do3z1_b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:center-focus" /></template>

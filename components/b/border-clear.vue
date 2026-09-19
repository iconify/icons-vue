<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvvx_2iyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gvvx_2iyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:border-clear" /></template>

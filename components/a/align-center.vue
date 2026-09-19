<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4e1gyb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p4e1gyb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:align-center" /></template>

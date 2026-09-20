<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv-1j60oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fv-1j60oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-down" /></template>

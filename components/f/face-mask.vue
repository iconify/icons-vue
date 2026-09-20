<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufz89ibmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ufz89ibmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:face-mask" /></template>

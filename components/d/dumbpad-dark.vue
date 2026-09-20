<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2mx2ubfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d2mx2ubfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbpad-dark" /></template>

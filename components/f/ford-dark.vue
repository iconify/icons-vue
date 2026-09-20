<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgi78ebgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sgi78ebgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ford-dark" /></template>

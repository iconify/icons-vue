<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp8-geliw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cp8-geliw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:compreface-dark" /></template>

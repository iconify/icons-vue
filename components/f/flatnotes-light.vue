<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf32sibdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gf32sibdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flatnotes-light" /></template>

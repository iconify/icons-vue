<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvxo4mbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zvxo4mbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:citibank-light" /></template>

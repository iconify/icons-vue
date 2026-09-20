<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk5-3bb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uk5-3bb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filameter" /></template>

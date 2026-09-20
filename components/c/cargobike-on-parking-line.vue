<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9b49ybjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w9b49ybjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cargobike-on-parking-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w96p14lvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w96p14lvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bind-9" /></template>

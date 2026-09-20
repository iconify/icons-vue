<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icrz6k5dk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="icrz6k5dk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:add-filter" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx98c1b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="rx98c1b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:battery-upright-low" /></template>

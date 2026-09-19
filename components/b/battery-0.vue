<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzhxep-4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fzhxep-4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:battery-0" /></template>

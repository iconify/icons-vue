<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv2ls5b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gv2ls5b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:health" /></template>

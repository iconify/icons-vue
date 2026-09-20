<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dllqc_nsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dllqc_nsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:align-objects-centered" /></template>

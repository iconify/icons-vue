<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miolbrbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="miolbrbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:avianex" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzlin--rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mzlin--rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:arrow-thick-right" /></template>

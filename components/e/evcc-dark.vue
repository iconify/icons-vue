<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eff2g6_ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eff2g6_ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:evcc-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5x6prmfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l5x6prmfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lightningrod-light" /></template>

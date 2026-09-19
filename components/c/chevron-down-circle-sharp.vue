<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctl2aebre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ctl2aebre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chevron-down-circle-sharp" /></template>

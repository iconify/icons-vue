<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doicf7bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="doicf7bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:beaker-sharp" /></template>

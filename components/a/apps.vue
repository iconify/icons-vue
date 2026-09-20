<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhu5enmfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rhu5enmfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:apps" /></template>

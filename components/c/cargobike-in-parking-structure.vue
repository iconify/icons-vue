<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyb2kkmwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qyb2kkmwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cargobike-in-parking-structure" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_6u2mhvb.css';
import '../../css/q/qm-3n6bvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_6u2mhvb"/><path class="qm-3n6bvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:golf" /></template>

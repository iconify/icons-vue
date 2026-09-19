<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp_b1m3ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bp_b1m3ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:conda-forge" /></template>

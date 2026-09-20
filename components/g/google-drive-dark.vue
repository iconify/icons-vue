<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azc14govv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="azc14govv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-drive-dark" /></template>

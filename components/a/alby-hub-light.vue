<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjo1_vbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cjo1_vbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alby-hub-light" /></template>

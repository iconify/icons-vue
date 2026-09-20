<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlazgl4ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dlazgl4ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-nomad-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-_innbce.css';
import '../../css/k/khl7ijbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-_innbce"/><path class="khl7ijbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-pulse-bold-duotone" /></template>

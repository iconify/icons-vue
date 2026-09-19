<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs1tkhbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rs1tkhbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:briefcase-sharp" /></template>

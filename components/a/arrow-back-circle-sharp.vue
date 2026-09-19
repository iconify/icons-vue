<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_pfwqd_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d_pfwqd_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:arrow-back-circle-sharp" /></template>

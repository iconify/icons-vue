<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/almjracyr.css';
import '../../css/l/la0xxkb4z.css';
import '../../css/n/n0jc1kb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="almjracyr"/><path class="la0xxkb4z"/><path class="n0jc1kb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-security-compliance-center-workload-protection" /></template>

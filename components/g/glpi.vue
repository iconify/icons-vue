<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5o3f9vcr.css';
import '../../css/w/w_tn9pbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t5o3f9vcr"/><path class="w_tn9pbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:glpi" /></template>

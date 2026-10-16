<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8e-izr_t.css';
import '../../css/f/fxil81qql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x8e-izr_t"/><path class="fxil81qql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-pouch-48" /></template>

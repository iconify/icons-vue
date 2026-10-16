<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gerffvb_e.css';
import '../../css/v/v5ofbw7zr.css';
import '../../css/m/m91h_kbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gerffvb_e"/><path class="v5ofbw7zr"/><path class="m91h_kbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-9v-48" /></template>

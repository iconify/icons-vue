<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0hk8168n.css';
import '../../css/e/e5i_hobjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m0hk8168n"/><path class="e5i_hobjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:luna-dashboard-light" /></template>

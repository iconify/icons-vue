<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfmop767n.css';
import '../../css/r/r5try_ncs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gfmop767n"/><path class="r5try_ncs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bridge-48-bold" /></template>

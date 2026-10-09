<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra-t_bbyc.css';
import '../../css/c/c7l7flb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ra-t_bbyc"/><path class="c7l7flb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-type2-48-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahmy5tb-o.css';
import '../../css/o/o3s572blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ahmy5tb-o"/><path class="o3s572blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:copy-48-bold" /></template>

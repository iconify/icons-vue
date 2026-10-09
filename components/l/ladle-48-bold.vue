<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oshhv4dvv.css';
import '../../css/o/ohv239ijk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oshhv4dvv"/><path class="ohv239ijk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ladle-48-bold" /></template>

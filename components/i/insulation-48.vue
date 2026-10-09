<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvggpac7z.css';
import '../../css/n/nooi5tb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wvggpac7z"/><path class="nooi5tb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:insulation-48" /></template>

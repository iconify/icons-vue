<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjcnosa2s.css';
import '../../css/i/i7hjkjq5j.css';
import '../../css/e/esibc_bpa.css';
import '../../css/b/bdrvyebhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wjcnosa2s"/><path class="i7hjkjq5j"/><path class="esibc_bpa"/><path class="bdrvyebhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:department" /></template>

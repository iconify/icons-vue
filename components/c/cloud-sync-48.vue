<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szla-yy9o.css';
import '../../css/g/g59d8ymwp.css';
import '../../css/v/vghnpubvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="szla-yy9o"/><path class="g59d8ymwp"/><path class="vghnpubvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-sync-48" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-hb89b0y.css';
import '../../css/q/qm_24p8td.css';
import '../../css/p/p97rajbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z-hb89b0y"/><path class="qm_24p8td"/><path class="p97rajbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coffee-machine-48" /></template>

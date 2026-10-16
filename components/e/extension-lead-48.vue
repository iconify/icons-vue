<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um_1f_zem.css';
import '../../css/t/txa3dwb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="um_1f_zem"/><path class="txa3dwb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:extension-lead-48" /></template>

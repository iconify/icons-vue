<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsmhpgwcs.css';
import '../../css/f/fh8g7ab6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tsmhpgwcs"/><path class="fh8g7ab6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:code-block-48" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa1bric-y.css';
import '../../css/s/s_f2_dbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sa1bric-y"/><path class="s_f2_dbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:biochar-48" /></template>

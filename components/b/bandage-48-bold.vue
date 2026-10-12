<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joh4xhb-o.css';
import '../../css/m/md8r-wrpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="joh4xhb-o"/><path class="md8r-wrpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bandage-48-bold" /></template>

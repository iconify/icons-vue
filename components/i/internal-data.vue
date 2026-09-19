<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2vbowdbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i2vbowdbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:internal-data" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm-2geb9q.css';
import '../../css/n/n33vuzbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mm-2geb9q"/><path class="n33vuzbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dam-48" /></template>

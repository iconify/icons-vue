<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf3a7wbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sf3a7wbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:justice" /></template>

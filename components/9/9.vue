<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw2os6bdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rw2os6bdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:9" /></template>

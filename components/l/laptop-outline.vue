<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6nrgy6io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r6nrgy6io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:laptop-outline" /></template>

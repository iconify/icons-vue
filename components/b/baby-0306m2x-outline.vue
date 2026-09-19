<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lehjgzbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lehjgzbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:baby-0306m2x-outline" /></template>

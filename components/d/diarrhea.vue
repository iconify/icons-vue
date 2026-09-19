<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msx7ap0di.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="msx7ap0di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:diarrhea" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eva2sp1dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="eva2sp1dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:deepfake-technology-1-remix" /></template>

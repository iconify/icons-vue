<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u19doiuhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u19doiuhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:hierarchy-15-solid" /></template>

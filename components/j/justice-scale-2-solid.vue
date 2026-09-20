<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe43akbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="oe43akbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:justice-scale-2-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sohy9t3it.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sohy9t3it"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:factory-plant-solid" /></template>

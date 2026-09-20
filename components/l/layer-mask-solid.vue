<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zunribbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zunribbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:layer-mask-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci7s_f6sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ci7s_f6sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:check-thick" /></template>

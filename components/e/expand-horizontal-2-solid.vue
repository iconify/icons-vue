<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcqfy0b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jcqfy0b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:expand-horizontal-2-solid" /></template>

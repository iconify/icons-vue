<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtc7irb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mtc7irb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:invisible-1-solid" /></template>

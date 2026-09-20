<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1bziabvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t1bziabvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:fork-plate-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blt9aqlsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="blt9aqlsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:delete-row-solid" /></template>

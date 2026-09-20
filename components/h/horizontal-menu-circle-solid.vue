<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt9l5qbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jt9l5qbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:horizontal-menu-circle-solid" /></template>

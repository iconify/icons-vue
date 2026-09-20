<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgdli1bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pgdli1bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:cao-dai-solid" /></template>

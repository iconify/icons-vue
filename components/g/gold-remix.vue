<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej5e9xjrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ej5e9xjrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:gold-remix" /></template>

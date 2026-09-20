<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgtah-2oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cgtah-2oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:eye-optic-remix" /></template>

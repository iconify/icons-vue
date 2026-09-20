<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjl42vbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kjl42vbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:braille-blind-solid" /></template>

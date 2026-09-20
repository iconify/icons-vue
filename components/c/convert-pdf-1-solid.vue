<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp10abbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bp10abbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:convert-pdf-1-solid" /></template>

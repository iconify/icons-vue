<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paa18-wwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="paa18-wwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:fit-to-width-square-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hteldcbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hteldcbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:battery-low-3-solid" /></template>

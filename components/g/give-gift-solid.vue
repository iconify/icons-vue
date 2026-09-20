<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6g06eeaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="g6g06eeaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:give-gift-solid" /></template>

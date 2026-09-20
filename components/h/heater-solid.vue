<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jipkl1aqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jipkl1aqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:heater-solid" /></template>

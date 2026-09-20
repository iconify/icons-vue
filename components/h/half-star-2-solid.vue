<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f35nuybus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f35nuybus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:half-star-2-solid" /></template>

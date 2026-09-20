<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltoh_6b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ltoh_6b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:insert-side-solid" /></template>

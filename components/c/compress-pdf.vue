<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwd061b5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fwd061b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:compress-pdf" /></template>

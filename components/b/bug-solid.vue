<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byjkoudzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="byjkoudzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:bug-solid" /></template>

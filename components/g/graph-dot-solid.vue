<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur-7fqmse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ur-7fqmse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:graph-dot-solid" /></template>

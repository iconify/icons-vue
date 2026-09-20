<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbos_mlra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jbos_mlra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:cloud-16" /></template>

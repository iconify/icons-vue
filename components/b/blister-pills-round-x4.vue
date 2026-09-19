<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmwv8bbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pmwv8bbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blister-pills-round-x4" /></template>

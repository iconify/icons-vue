<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg5ix3lix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rg5ix3lix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dressing-table-01" /></template>

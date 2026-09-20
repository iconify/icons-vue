<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz__jgbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz__jgbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circuit-cell-plus" /></template>

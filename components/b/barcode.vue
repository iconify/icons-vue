<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shbl2zbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shbl2zbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:barcode" /></template>

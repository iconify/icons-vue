<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe_z-t4nf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe_z-t4nf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:direction-horizontal" /></template>

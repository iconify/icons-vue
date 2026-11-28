<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d26h4ib5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d26h4ib5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cloud-hail" /></template>

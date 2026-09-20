<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb-_z3bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb-_z3bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-alert-outline" /></template>

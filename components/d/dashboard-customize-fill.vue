<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwvj7pbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwvj7pbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:dashboard-customize-fill" /></template>

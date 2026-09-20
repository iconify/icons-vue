<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swgmve7ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swgmve7ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:arrow-circle-right" /></template>

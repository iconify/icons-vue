<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhh071ixv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhh071ixv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:basket-check-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbwhxmxke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbwhxmxke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:globe-plus" /></template>

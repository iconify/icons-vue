<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl13osb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="dl13osb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-horizontal-menu-left" /></template>

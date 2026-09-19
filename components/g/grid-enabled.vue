<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz-65_bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lz-65_bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:grid-enabled" /></template>

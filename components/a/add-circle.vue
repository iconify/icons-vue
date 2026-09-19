<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azlztwo3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azlztwo3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:add-circle" /></template>

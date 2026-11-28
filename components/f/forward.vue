<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/naytc9bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="naytc9bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:forward" /></template>

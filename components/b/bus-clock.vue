<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvwy_vb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvwy_vb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bus-clock" /></template>

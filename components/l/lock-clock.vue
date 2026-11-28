<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocufuiigg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocufuiigg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:lock-clock" /></template>

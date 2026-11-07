<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7wwok4ts.css';
import '../../css/o/otho62bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7wwok4ts"/><path class="otho62bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:logout-bold" /></template>

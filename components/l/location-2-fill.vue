<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly9sq0blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly9sq0blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:location-2-fill" /></template>

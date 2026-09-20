<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smgqmefax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="smgqmefax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fish-head-beside-barbed-hook-on-line-under-ice" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyxd_0z0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fyxd_0z0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hairy-caterpillar" /></template>

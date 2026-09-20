<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxzun484g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxzun484g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:garage" /></template>

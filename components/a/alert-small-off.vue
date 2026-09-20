<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1ef45pxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1ef45pxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alert-small-off" /></template>

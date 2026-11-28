<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_udarb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_udarb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cookie" /></template>

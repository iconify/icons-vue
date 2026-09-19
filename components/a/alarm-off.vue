<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpy0vg23g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpy0vg23g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:alarm-off" /></template>

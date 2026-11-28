<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_t2o4b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_t2o4b7l primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-down-left-duotone" /></template>

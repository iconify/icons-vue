<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jps-cbb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jps-cbb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:bell-off" /></template>

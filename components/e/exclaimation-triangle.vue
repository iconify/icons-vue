<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oon171yhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oon171yhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:exclaimation-triangle" /></template>

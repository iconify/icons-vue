<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2q3-9bye.css';
import '../../css/z/zbzhdcacm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2q3-9bye"/><path class="zbzhdcacm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:import" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dse1e7dvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dse1e7dvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:laptop" /></template>

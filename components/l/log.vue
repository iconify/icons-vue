<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h65ixdb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h65ixdb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:log" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti6n5kb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti6n5kb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-arrow-down" /></template>

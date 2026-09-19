<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rslle7b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rslle7b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:drop-down" /></template>

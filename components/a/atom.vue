<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gey8zob9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gey8zob9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:atom" /></template>

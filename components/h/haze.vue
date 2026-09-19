<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt60lmigj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt60lmigj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:haze" /></template>

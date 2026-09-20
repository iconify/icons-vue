<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czc233s8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czc233s8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:infinity-off" /></template>

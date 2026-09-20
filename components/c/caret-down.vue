<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofwe9nvry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofwe9nvry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:caret-down" /></template>

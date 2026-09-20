<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rabq7vbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rabq7vbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:flag" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofavgsb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofavgsb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-2-question" /></template>

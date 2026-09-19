<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h205pf10p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h205pf10p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-dollar" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rou2qjbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rou2qjbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:logo-stack-overflow" /></template>

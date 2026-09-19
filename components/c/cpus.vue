<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oge-2sbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oge-2sbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:cpus" /></template>

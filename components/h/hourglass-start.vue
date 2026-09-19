<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2dw7_bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h2dw7_bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:hourglass-start" /></template>

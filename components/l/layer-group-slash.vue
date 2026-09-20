<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbgv9bcsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbgv9bcsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:layer-group-slash" /></template>

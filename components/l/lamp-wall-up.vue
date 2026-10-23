<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz69lobeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz69lobeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:lamp-wall-up" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un8mlebwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un8mlebwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-circle-right-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un8nmixra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un8nmixra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-quarter-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez7i28aau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ez7i28aau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:box-open" /></template>

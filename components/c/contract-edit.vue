<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz1r_1b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz1r_1b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:contract-edit" /></template>

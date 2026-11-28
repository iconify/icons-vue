<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjbym0xls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary rjbym0xls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:heading-1-duotone" /></template>

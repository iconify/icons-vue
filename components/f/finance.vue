<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_hmpwg1c.css';
import '../../css/e/ej-f8xcot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_hmpwg1c"/><path class="ej-f8xcot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:finance" /></template>

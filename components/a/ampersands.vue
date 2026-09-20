<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmh5-ebmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmh5-ebmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:ampersands" /></template>

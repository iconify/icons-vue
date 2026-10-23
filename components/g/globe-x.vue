<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtu1fhbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtu1fhbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:globe-x" /></template>

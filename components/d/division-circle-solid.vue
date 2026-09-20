<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1frjwb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o1frjwb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:division-circle-solid" /></template>

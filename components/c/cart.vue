<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oay60c9mk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oay60c9mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cart" /></template>

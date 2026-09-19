<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oew3rhbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oew3rhbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:layer" /></template>

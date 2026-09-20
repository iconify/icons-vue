<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhixw6bhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fhixw6bhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hourglass" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0iivbcas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0iivbcas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:binoculars-filled" /></template>

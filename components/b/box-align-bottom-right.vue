<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oablwkbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oablwkbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:box-align-bottom-right" /></template>

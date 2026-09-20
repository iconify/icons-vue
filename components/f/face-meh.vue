<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4_i65b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4_i65b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:face-meh" /></template>

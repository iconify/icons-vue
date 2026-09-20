<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_toloycw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_toloycw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-bigtable" /></template>

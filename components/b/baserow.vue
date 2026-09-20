<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v381uuv_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v381uuv_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:baserow" /></template>

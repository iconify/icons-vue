<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta_6slvwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ta_6slvwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:exoscale" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef-7fk3tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef-7fk3tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dhl" /></template>

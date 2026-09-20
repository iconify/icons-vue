<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slq3vpbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slq3vpbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:location-minus-filled" /></template>

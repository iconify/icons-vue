<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-u58ub6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-u58ub6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:checkmarx" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lghfdm1ci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lghfdm1ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:chocolatey" /></template>

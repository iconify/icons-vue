<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua73idyup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":52,"height":28};
const content = `<path clip-rule="evenodd" class="ua73idyup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cisco-dark" /></template>

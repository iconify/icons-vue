<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kon4bwbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kon4bwbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:autoit" /></template>

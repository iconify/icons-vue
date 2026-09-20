<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l628z4bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l628z4bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:freelancermap" /></template>

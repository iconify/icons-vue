<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb7_l_nwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb7_l_nwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ds-automobiles" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh5zgdcot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dh5zgdcot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:istio" /></template>

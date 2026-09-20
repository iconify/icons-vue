<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwiq2935u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwiq2935u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fraunhofer-gesellschaft" /></template>

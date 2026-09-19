<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t35_r-06s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t35_r-06s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-bulb" /></template>

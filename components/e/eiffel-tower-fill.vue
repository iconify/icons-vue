<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as9abwbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as9abwbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eiffel-tower-fill" /></template>

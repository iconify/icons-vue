<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2--ctuld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2--ctuld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-expressionless-sharp-fill" /></template>

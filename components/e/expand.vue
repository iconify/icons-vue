<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj1g30blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj1g30blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:expand" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gaxm8-_2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gaxm8-_2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-baht-line" /></template>

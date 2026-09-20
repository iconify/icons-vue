<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1jxl6boa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1jxl6boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:lottiefiles" /></template>

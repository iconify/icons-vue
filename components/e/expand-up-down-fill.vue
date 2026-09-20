<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icgs5jzlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icgs5jzlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-up-down-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt9wrr88u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt9wrr88u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:forecastcloud-moon-tear" /></template>

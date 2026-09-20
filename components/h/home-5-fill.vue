<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn2j6ebje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn2j6ebje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-5-fill" /></template>

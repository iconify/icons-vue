<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pho01gbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pho01gbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-j-square-solid" /></template>

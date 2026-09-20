<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/too40e6yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="too40e6yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:clock-seven" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz6a-wbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz6a-wbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:amazonelasticache" /></template>

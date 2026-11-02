<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-euov8ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-euov8ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:house-heart-line" /></template>

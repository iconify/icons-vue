<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8735r-je.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8735r-je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:coffee-sharp" /></template>

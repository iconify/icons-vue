<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glkt4nbay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glkt4nbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-inner-fill" /></template>

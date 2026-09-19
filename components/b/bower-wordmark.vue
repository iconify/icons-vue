<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h16-qvbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="h16-qvbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:bower-wordmark" /></template>

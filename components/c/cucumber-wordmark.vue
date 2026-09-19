<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyrluiq9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vyrluiq9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:cucumber-wordmark" /></template>

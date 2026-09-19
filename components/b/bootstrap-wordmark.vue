<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxb0eifos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uxb0eifos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:bootstrap-wordmark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8c9z9b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="t8c9z9b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:hyperv" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtx52bclv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jtx52bclv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:flyway" /></template>

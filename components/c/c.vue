<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfpibsb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lfpibsb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:c" /></template>

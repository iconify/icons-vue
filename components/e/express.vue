<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ollmjwbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ollmjwbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:express" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewef_zbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ewef_zbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:intellij" /></template>

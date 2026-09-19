<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a58u95buk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="a58u95buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:azuresqldatabase" /></template>

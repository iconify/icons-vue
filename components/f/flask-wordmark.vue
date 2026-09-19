<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6z79faub.css';
import '../../css/d/d7sn98bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="j6z79faub"/><path class="d7sn98bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:flask-wordmark" /></template>

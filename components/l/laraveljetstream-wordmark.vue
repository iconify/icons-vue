<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brftz6bit.css';
import '../../css/v/vj7j3db8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="brftz6bit"/><path class="vj7j3db8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:laraveljetstream-wordmark" /></template>

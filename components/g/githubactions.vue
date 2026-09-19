<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmqemt8zm.css';
import '../../css/k/katrf5x9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rmqemt8zm"/><path class="katrf5x9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:githubactions" /></template>

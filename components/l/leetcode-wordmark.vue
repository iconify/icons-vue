<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m58734bmb.css';
import '../../css/b/b3dakxwyz.css';
import '../../css/n/n8ps1yhvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="m58734bmb"/><path class="b3dakxwyz"/><path class="n8ps1yhvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:leetcode-wordmark" /></template>

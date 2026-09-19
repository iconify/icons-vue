<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l42ge3b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l42ge3b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:jiraalign" /></template>

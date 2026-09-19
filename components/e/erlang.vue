<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llmvx1bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="llmvx1bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:erlang" /></template>

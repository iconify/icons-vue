<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fozui9hfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="fozui9hfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:elixir-wordmark" /></template>

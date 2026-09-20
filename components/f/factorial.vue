<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5zwpxb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="q5zwpxb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:factorial" /></template>

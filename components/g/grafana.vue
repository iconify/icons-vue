<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7bnz5mfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="w7bnz5mfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:grafana" /></template>

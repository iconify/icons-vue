<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to_00xq7r.css';
import '../../css/s/sd17u1b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="to_00xq7r"/><path class="sd17u1b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:fastify" /></template>

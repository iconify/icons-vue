<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtx-7sn0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dtx-7sn0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:codeigniter" /></template>

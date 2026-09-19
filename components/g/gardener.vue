<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tob8s0bkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tob8s0bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:gardener" /></template>

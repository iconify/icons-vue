<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3onifb8e.css';
import '../../css/n/n9vml882r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z3onifb8e"/><path class="n9vml882r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heated-towel-rail-20-bold" /></template>

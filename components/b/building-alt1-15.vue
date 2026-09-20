<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjzqn06_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pjzqn06_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:building-alt1-15" /></template>

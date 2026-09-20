<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfem4tb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gfem4tb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:car-rental" /></template>

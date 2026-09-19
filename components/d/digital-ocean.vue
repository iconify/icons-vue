<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajrmk5k8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ajrmk5k8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:digital-ocean" /></template>

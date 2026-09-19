<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm5f1qe_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="dm5f1qe_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:fort-awesome-alt" /></template>

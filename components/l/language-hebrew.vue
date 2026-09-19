<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_k1ojhml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="e_k1ojhml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-hebrew" /></template>

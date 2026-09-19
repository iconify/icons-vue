<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egtos6b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="egtos6b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:advantage-circle" /></template>

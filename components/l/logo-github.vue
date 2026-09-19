<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0q_w7t3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b0q_w7t3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-github" /></template>

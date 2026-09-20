<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr_ae8lpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pr_ae8lpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:github-solid" /></template>

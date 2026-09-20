<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0kzj5b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z0kzj5b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:github-outline" /></template>

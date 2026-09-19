<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9uxiob0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f9uxiob0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:git-commit-sharp" /></template>

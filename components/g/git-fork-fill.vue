<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py6kwddky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py6kwddky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:git-fork-fill" /></template>

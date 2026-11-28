<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gciat2bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gciat2bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:git-commit-check" /></template>

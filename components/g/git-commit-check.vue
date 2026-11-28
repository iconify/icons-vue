<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plek-ib1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plek-ib1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:git-commit-check" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek9zqwbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ek9zqwbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:augmented-reality-bold" /></template>

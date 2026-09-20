<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfv63-bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfv63-bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flag-linear" /></template>

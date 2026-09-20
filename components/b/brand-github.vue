<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq__wbbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq__wbbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-github" /></template>

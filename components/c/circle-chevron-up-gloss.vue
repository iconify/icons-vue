<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9t3z0jdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9t3z0jdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-chevron-up-gloss" /></template>

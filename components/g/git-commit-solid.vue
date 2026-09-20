<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnopl_b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xnopl_b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:git-commit-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp2s9rbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tp2s9rbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-merge-16" /></template>

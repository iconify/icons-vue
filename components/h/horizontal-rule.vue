<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8fzx0j8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":16};
const content = `<path class="k8fzx0j8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:horizontal-rule" /></template>

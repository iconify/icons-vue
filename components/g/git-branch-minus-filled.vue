<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuam72hri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuam72hri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:git-branch-minus-filled" /></template>

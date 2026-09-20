<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixl5yb5fa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixl5yb5fa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-branch-minus" /></template>

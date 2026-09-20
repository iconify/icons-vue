<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_d2xhq5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_d2xhq5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-commit-24" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj4pwu2ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj4pwu2ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-commit-horizontal-line" /></template>

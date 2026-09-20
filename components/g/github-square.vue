<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nts4t-bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nts4t-bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:github-square" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3cou9bya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":402,"height":512};
const content = `<path class="e3cou9bya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:bluespec" /></template>

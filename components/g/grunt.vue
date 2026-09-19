<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg6t5bctu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":430,"height":512};
const content = `<path class="eg6t5bctu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:grunt" /></template>

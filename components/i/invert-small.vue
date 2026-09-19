<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csesmy2vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="csesmy2vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:invert-small" /></template>

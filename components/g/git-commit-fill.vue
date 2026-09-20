<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un0416bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un0416bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:git-commit-fill" /></template>

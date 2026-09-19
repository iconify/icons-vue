<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsqb0y01i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsqb0y01i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:github-alt" /></template>

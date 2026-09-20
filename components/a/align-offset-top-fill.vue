<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0y4ecb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0y4ecb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-offset-top-fill" /></template>

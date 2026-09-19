<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thm-z9rlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thm-z9rlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:circle-up" /></template>

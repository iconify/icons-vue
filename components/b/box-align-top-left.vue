<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9lm6ltaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9lm6ltaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:box-align-top-left" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh10_4bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh10_4bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-chevron-down-fill" /></template>

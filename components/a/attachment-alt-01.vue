<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqcgbpbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqcgbpbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:attachment-alt-01" /></template>

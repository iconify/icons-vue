<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhe7-4bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhe7-4bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-circle-down-right" /></template>

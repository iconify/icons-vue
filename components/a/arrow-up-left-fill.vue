<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhyjf-b9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhyjf-b9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-left-fill" /></template>

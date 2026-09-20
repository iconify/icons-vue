<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro266hnbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro266hnbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:branch-solid" /></template>

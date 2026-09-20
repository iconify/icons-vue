<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9ngsnuyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9ngsnuyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-right-sharp-two-tone" /></template>

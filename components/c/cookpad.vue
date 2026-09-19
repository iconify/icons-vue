<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6mz-dumd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":717};
const content = `<path class="f6mz-dumd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:cookpad" /></template>

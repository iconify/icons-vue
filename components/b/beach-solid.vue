<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dis9ojbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dis9ojbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:beach-solid" /></template>

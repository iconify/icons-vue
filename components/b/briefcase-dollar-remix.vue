<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt4e53b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bt4e53b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:briefcase-dollar-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya6rrexwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ya6rrexwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:hand-thumb-down-20-solid" /></template>

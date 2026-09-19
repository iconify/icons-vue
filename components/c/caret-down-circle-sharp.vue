<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkd6yqz1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jkd6yqz1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:caret-down-circle-sharp" /></template>

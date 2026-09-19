<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgm-rnbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cgm-rnbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:chevron-collapse-sharp" /></template>

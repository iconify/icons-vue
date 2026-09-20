<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2w7s7nlt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v2w7s7nlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:antibody" /></template>

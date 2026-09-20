<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp7je4b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fp7je4b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:heart-with-crack" /></template>

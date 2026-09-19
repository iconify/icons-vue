<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjsiaz5ow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rjsiaz5ow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:folder-fill" /></template>

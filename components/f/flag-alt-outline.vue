<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwhsll-1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nwhsll-1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:flag-alt-outline" /></template>

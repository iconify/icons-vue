<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzzn6pbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="bzzn6pbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:lawyer" /></template>

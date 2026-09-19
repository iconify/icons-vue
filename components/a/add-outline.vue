<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1_exgbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e1_exgbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:add-outline" /></template>

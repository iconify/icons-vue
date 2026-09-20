<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap4nx0b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ap4nx0b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:left-circle-outline" /></template>

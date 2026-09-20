<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azkzdtbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="azkzdtbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:field-hockey-stick-with-ball" /></template>

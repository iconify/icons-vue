<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3-ah3bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t3-ah3bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:basketball-15" /></template>

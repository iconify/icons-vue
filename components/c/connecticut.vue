<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok_gg1bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ok_gg1bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:connecticut" /></template>

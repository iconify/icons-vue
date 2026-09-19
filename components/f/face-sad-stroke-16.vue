<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo5a97nhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bo5a97nhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:face-sad-stroke-16" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs93c7boo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qs93c7boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:chevron-left" /></template>

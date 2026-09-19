<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8k2-tb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="j8k2-tb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:face-with-no-good-gesture" /></template>

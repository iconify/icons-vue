<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/encu6lmxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="encu6lmxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:checkmark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2f7d8bkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s2f7d8bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:calendar-no-access-outline" /></template>

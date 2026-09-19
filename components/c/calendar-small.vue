<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcdmvd9fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xcdmvd9fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:calendar-small" /></template>

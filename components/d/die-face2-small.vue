<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocolddcnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ocolddcnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:die-face2-small" /></template>

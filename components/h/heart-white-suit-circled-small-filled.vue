<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja9-_j11q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ja9-_j11q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:heart-white-suit-circled-small-filled" /></template>

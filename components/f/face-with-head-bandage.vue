<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xus7n3b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xus7n3b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:face-with-head-bandage" /></template>

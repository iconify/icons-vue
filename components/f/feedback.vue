<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rystv1tqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rystv1tqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:feedback" /></template>

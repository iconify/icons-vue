<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqo98j5vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kqo98j5vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:fire" /></template>

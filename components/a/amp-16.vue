<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q47b6fb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q47b6fb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:amp-16" /></template>

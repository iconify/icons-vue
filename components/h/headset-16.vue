<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-he5nhuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e-he5nhuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:headset-16" /></template>

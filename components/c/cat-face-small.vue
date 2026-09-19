<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e92jr9qgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="e92jr9qgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:cat-face-small" /></template>

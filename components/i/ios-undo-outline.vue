<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax4xf9blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ax4xf9blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-undo-outline" /></template>

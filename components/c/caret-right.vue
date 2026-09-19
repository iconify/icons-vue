<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou1lpbckg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ou1lpbckg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:caret-right" /></template>

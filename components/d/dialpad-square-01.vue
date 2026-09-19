<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afu0z20lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afu0z20lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dialpad-square-01" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyv1r9bwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oyv1r9bwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bolt-off-20" /></template>

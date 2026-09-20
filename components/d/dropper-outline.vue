<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueti9nbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ueti9nbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:dropper-outline" /></template>

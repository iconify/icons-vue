<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3brbnu2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b3brbnu2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bluetooth-outline" /></template>

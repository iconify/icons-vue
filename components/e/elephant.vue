<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-62fle1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b-62fle1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:elephant" /></template>
